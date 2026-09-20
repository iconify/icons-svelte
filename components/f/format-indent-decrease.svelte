<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksi8u2bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksi8u2bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-indent-decrease" {...props}></Icon>
