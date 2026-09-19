<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo7khsgtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo7khsgtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chess-queen" {...props}></Icon>
