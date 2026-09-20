<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b51trz_uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b51trz_uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:fingerprint-line" {...props}></Icon>
