<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fclsd1b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fclsd1b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:radio-button-indeterminate" {...props}></Icon>
