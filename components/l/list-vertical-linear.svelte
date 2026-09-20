<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fvnj3qbjd.css';
import '../../css/k/kh_4bzbdf.css';
import '../../css/o/o2bnwltsv.css';
import '../../css/r/r9gp_ab3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fvnj3qbjd"/><path class="kh_4bzbdf"/><path class="o2bnwltsv"/><path class="r9gp_ab3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-vertical-linear" {...props}></Icon>
