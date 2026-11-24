<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akdj-thul.css';
import '../../css/g/gb1ceubcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akdj-thul"/><path class="gb1ceubcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-fog-filled" {...props}></Icon>
