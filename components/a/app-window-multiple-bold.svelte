<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i59_vpbwp.css';
import '../../css/c/cmhxciomr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i59_vpbwp"/><path class="cmhxciomr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:app-window-multiple-bold" {...props}></Icon>
