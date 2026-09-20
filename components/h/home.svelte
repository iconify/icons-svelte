<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo7xkkbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo7xkkbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:home" {...props}></Icon>
