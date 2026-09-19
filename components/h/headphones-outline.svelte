<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd5lbcb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd5lbcb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:headphones-outline" {...props}></Icon>
