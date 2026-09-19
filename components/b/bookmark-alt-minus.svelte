<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc771vb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc771vb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bookmark-alt-minus" {...props}></Icon>
