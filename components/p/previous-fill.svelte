<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4jvy7b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4jvy7b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:previous-fill" {...props}></Icon>
