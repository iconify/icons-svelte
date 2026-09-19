<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bam1n0b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bam1n0b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hospital-user" {...props}></Icon>
