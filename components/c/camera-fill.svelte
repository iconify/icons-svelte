<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzditrbqy.css';
import '../../css/b/bl1wln6eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="xzditrbqy"/><path class="bl1wln6eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:camera-fill" {...props}></Icon>
