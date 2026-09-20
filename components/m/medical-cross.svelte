<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx7djlehs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wx7djlehs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:medical-cross" {...props}></Icon>
