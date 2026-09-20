<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv6ftnbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv6ftnbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:book-minus-solid" {...props}></Icon>
