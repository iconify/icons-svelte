<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al1wpe50a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al1wpe50a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chess-rook" {...props}></Icon>
