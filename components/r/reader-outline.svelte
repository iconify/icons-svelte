<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyolq2bek.css';
import '../../css/j/jo-7oophi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="vyolq2bek"/><path class="jo-7oophi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:reader-outline" {...props}></Icon>
