<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcjfcjp-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcjfcjp-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-vert-center-simple-line" {...props}></Icon>
