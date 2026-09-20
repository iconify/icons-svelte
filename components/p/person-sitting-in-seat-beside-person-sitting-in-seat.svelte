<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sld4zn5wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sld4zn5wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-sitting-in-seat-beside-person-sitting-in-seat" {...props}></Icon>
