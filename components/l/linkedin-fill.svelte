<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg7j1hkpt.css';
import '../../css/y/y1ghfdd7v.css';
import '../../css/w/w3nzclc_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg7j1hkpt"/><rect class="y1ghfdd7v"/><circle class="w3nzclc_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:linkedin-fill" {...props}></Icon>
