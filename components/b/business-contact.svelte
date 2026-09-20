<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr2tweb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="zr2tweb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:business-contact" {...props}></Icon>
