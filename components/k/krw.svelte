<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc78ikbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":31,"height":24};
const content = `<path class="lc78ikbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:krw" {...props}></Icon>
