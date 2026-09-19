<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yydt5mb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yydt5mb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:phone-book-filled" {...props}></Icon>
