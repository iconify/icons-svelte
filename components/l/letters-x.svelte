<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvcqgdbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvcqgdbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-x" {...props}></Icon>
