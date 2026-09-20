<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbg5zkbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qbg5zkbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:mojo" {...props}></Icon>
