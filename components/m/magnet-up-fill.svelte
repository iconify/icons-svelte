<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v58p9ubwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v58p9ubwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:magnet-up-fill" {...props}></Icon>
