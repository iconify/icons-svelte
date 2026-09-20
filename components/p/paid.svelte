<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdu0sgbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="hdu0sgbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:paid" {...props}></Icon>
