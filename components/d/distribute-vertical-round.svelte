<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk73n3bfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk73n3bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:distribute-vertical-round" {...props}></Icon>
