<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0x_rfbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0x_rfbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:apple-alt" {...props}></Icon>
