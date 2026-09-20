<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qod50dvnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qod50dvnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:merge-vertical" {...props}></Icon>
