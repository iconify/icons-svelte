<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_4wmij0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="b_4wmij0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:helm" {...props}></Icon>
