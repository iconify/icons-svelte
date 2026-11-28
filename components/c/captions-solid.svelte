<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i__hsmivx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i__hsmivx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:captions-solid" {...props}></Icon>
