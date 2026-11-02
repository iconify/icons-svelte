<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tly86gwbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tly86gwbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:basket-2-fill" {...props}></Icon>
