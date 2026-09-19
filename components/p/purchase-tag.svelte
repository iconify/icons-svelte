<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw9kcbb2m.css';
import '../../css/z/zn5t45b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw9kcbb2m"/><circle class="zn5t45b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:purchase-tag" {...props}></Icon>
