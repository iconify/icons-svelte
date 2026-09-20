<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzy3mpo1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="vzy3mpo1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:news" {...props}></Icon>
