<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbxmv5lgw.css';
import '../../css/l/lbz_afxlg.css';
import '../../css/g/gc5bzfbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dbxmv5lgw"/><path class="lbz_afxlg"/><path class="gc5bzfbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:githubactions-wordmark" {...props}></Icon>
