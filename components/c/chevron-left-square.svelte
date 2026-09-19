<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjd33qpzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjd33qpzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:chevron-left-square" {...props}></Icon>
