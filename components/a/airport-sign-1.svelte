<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxt3-pber.css';
import '../../css/k/k18y-k1ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxt3-pber"/><path class="k18y-k1ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:airport-sign-1" {...props}></Icon>
