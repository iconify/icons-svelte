<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh070wbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh070wbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:essential-oil-diffuser-alt" {...props}></Icon>
