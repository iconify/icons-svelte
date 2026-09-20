<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzx8w820q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzx8w820q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:check-bookmark" {...props}></Icon>
