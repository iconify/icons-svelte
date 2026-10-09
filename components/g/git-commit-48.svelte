<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3bstg6yn.css';
import '../../css/h/h4fi9ef0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r3bstg6yn"/><path class="h4fi9ef0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:git-commit-48" {...props}></Icon>
