<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efl8wly-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="efl8wly-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:postscript" {...props}></Icon>
