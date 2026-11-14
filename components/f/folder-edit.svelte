<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu09wfb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gu09wfb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-edit" {...props}></Icon>
