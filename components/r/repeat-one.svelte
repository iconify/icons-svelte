<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxlx4zb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zxlx4zb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:repeat-one" {...props}></Icon>
