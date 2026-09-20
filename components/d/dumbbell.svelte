<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orcy-v-bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="orcy-v-bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dumbbell" {...props}></Icon>
