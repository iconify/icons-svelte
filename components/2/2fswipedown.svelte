<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw19jlmwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="yw19jlmwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:2fswipedown" {...props}></Icon>
