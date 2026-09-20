<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs4pc5mry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zs4pc5mry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layer-fill" {...props}></Icon>
