<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc0ra4bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc0ra4bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:roku" {...props}></Icon>
