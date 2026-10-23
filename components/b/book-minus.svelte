<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf2j8ceay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf2j8ceay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:book-minus" {...props}></Icon>
