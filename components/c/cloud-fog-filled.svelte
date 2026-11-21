<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akdj-thul.css';
import '../../css/v/va0b3zbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akdj-thul"/><path class="va0b3zbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-fog-filled" {...props}></Icon>
