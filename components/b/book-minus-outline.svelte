<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9z3nfbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9z3nfbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-minus-outline" {...props}></Icon>
