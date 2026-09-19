<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogau4npip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ogau4npip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:folder" {...props}></Icon>
