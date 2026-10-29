<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vef0kgbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vef0kgbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-solid" {...props}></Icon>
