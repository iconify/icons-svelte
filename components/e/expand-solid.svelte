<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjyjkxb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qjyjkxb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:expand-solid" {...props}></Icon>
