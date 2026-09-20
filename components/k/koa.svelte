<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrnhx7bwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrnhx7bwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:koa" {...props}></Icon>
