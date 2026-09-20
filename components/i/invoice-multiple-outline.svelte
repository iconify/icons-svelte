<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjmeoibsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjmeoibsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-multiple-outline" {...props}></Icon>
