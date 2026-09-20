<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_o4c-fyf.css';
import '../../css/b/bafc_qt6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_o4c-fyf"/><path class="bafc_qt6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:eye" {...props}></Icon>
