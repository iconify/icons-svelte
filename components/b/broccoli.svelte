<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2axqqb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="z2axqqb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:broccoli" {...props}></Icon>
