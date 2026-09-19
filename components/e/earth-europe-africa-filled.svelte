<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od4db_i1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="od4db_i1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:earth-europe-africa-filled" {...props}></Icon>
