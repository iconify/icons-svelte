<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzf2fwb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzf2fwb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:expand" {...props}></Icon>
