<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbp53x0bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbp53x0bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:not-equal-variant" {...props}></Icon>
