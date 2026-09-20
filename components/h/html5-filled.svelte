<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsh2eobjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsh2eobjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:html5-filled" {...props}></Icon>
