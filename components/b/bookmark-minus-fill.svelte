<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c88y4sg0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c88y4sg0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:bookmark-minus-fill" {...props}></Icon>
