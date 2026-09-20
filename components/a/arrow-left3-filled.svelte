<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv8z7nfju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv8z7nfju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-left3-filled" {...props}></Icon>
