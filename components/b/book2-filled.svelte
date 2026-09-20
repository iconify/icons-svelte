<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-xq3_bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-xq3_bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:book2-filled" {...props}></Icon>
