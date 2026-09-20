<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt4a0s1ni.css';
import '../../css/y/yedu7zb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="mt4a0s1ni"/><path class="yedu7zb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-interpreter-services" {...props}></Icon>
