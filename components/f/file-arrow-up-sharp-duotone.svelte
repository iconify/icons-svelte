<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/w/w5c8y-14a.css';
import '../../css/g/g6hnddcux.css';
import '../../css/k/kokqw6but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w5c8y-14a"/><path clip-rule="evenodd" class="g6hnddcux"/><path class="kokqw6but"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-arrow-up-sharp-duotone" {...props}></Icon>
