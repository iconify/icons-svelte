<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbf_zkbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="zbf_zkbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:collaborator" {...props}></Icon>
