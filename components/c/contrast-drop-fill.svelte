<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztmgx140y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztmgx140y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:contrast-drop-fill" {...props}></Icon>
