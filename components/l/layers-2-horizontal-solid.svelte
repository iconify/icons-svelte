<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-54k2y9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-54k2y9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-2-horizontal-solid" {...props}></Icon>
