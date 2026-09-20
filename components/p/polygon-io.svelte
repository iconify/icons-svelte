<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vprg18qvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":290,"height":79};
const content = `<path clip-rule="evenodd" class="vprg18qvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:polygon-io" {...props}></Icon>
