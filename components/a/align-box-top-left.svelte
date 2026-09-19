<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl0hz87mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl0hz87mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-box-top-left" {...props}></Icon>
