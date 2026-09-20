<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8yady8wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8yady8wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cart-check" {...props}></Icon>
