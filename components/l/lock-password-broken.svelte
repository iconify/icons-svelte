<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uwdynnbji.css';
import '../../css/x/xnnhmccbq.css';
import '../../css/e/eyig6k37j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uwdynnbji"/><path class="xnnhmccbq"/><path class="eyig6k37j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lock-password-broken" {...props}></Icon>
