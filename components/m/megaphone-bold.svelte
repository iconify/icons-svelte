<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5uwghb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5uwghb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:megaphone-bold" {...props}></Icon>
