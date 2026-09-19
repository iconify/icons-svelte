<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f681u-1lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f681u-1lk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clock-4-filled" {...props}></Icon>
