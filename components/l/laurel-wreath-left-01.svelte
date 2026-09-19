<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv4mebbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv4mebbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:laurel-wreath-left-01" {...props}></Icon>
