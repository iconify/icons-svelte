<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me_w7zb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="me_w7zb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fingerprint-2-fill" {...props}></Icon>
