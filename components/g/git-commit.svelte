<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhnstcuom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mhnstcuom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:git-commit" {...props}></Icon>
