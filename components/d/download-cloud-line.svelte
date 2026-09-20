<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqysygbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqysygbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:download-cloud-line" {...props}></Icon>
