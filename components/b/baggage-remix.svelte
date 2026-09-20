<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp9_yjb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zp9_yjb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:baggage-remix" {...props}></Icon>
