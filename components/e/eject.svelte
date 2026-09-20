<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv6th6b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="fv6th6b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:eject" {...props}></Icon>
