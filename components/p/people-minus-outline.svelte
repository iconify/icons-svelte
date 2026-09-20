<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bag5a7bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bag5a7bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:people-minus-outline" {...props}></Icon>
