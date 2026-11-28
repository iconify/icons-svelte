<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpnbl9yww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpnbl9yww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:fingerprint-lock" {...props}></Icon>
