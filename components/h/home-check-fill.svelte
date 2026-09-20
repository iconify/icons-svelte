<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw8shqb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw8shqb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:home-check-fill" {...props}></Icon>
