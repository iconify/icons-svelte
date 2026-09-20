<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2p--tysj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2p--tysj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dogecoin-doge-fill" {...props}></Icon>
