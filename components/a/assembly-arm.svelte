<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk1mzua3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hk1mzua3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:assembly-arm" {...props}></Icon>
