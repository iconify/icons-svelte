<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/m/m4ph6li3r.css';
import '../../css/c/cf1vlob_u.css';
import '../../css/y/yvc8aobsv.css';
import '../../css/y/yaz0d-yvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="m4ph6li3r"/><path class="cf1vlob_u"/><path class="yvc8aobsv"/><path class="yaz0d-yvj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:crowdin-logo" {...props}></Icon>
