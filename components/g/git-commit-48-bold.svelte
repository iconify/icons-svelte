<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf9mlfk3q.css';
import '../../css/t/tqy8z_h5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nf9mlfk3q"/><path class="tqy8z_h5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:git-commit-48-bold" {...props}></Icon>
