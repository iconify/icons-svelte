<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9huf1b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9huf1b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:receipt-search-filled" {...props}></Icon>
