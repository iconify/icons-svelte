<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avg0p0xjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avg0p0xjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:move-up-right" {...props}></Icon>
