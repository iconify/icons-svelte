<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0v-yo90b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t0v-yo90b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:mysql" {...props}></Icon>
