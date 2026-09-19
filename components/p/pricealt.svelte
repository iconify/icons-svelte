<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il9y_2n5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="il9y_2n5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pricealt" {...props}></Icon>
