<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo46cwbkr.css';
import '../../css/y/y1bea5b9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo46cwbkr"/><path class="y1bea5b9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:remix-js" {...props}></Icon>
