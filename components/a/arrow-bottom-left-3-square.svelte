<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxcczh6dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxcczh6dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-left-3-square" {...props}></Icon>
