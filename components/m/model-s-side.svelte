<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-2fixmoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-2fixmoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:model-s-side" {...props}></Icon>
