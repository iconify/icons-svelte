<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dukpz28sm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dukpz28sm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:document-popular-filled" {...props}></Icon>
