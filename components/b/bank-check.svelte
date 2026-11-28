<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9yp_ywja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9yp_ywja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bank-check" {...props}></Icon>
