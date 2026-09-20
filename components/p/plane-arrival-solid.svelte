<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7vlg2bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n7vlg2bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:plane-arrival-solid" {...props}></Icon>
