<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de2p3kbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="de2p3kbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:name" {...props}></Icon>
