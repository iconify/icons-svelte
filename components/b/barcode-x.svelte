<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdfcqb6dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdfcqb6dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:barcode-x" {...props}></Icon>
