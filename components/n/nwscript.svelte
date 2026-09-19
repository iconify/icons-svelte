<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkrmi-1du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tkrmi-1du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nwscript" {...props}></Icon>
