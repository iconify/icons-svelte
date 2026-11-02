<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zko-cjbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zko-cjbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bomb-line" {...props}></Icon>
