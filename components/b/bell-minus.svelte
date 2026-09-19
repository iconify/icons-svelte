<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1e2nrbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1e2nrbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bell-minus" {...props}></Icon>
