<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajs8ko0tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ajs8ko0tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-upright-slash" {...props}></Icon>
