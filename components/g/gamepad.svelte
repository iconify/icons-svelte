<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6w-lk-lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g6w-lk-lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:gamepad" {...props}></Icon>
