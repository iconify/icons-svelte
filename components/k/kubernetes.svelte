<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb50vv9xt.css';
import '../../css/d/ds9388b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hb50vv9xt"/><path class="ds9388b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:kubernetes" {...props}></Icon>
