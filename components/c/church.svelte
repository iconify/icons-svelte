<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm2hqdbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nm2hqdbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:church" {...props}></Icon>
