<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni_p_obvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni_p_obvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:museum-1-filled" {...props}></Icon>
