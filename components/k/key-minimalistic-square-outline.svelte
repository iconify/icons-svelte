<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtdmv7zzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vtdmv7zzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-minimalistic-square-outline" {...props}></Icon>
