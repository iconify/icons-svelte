<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrxb42skb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="jrxb42skb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:car-11" {...props}></Icon>
