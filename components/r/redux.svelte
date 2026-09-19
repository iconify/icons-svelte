<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odbl_absp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="odbl_absp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:redux" {...props}></Icon>
