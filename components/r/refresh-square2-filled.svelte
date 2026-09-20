<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt63arb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt63arb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:refresh-square2-filled" {...props}></Icon>
