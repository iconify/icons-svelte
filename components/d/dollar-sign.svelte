<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6432zb_d.css';
import '../../css/a/alc0ykp4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6432zb_d"/><path class="alc0ykp4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:dollar-sign" {...props}></Icon>
