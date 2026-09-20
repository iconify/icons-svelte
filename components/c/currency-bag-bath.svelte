<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-txjnb-q.css';
import '../../css/g/g13_2rbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-txjnb-q"/><path class="g13_2rbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:currency-bag-bath" {...props}></Icon>
