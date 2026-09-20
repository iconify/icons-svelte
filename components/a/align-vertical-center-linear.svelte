<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dzle42rhc.css';
import '../../css/e/eox6dq53k.css';
import '../../css/k/kah-p9bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dzle42rhc"/><path class="eox6dq53k"/><path class="kah-p9bbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-vertical-center-linear" {...props}></Icon>
