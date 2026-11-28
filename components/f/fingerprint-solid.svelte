<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de5-wl5rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de5-wl5rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fingerprint-solid" {...props}></Icon>
