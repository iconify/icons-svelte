<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/b/bbg_e0beb.css';
import '../../css/c/czb17zbdq.css';
import '../../css/a/ablr-2bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="bbg_e0beb"/><circle class="czb17zbdq"/><path class="ablr-2bmr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:pass-light" {...props}></Icon>
