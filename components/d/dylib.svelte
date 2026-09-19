<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knf8ffp_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":503,"height":512};
const content = `<path class="knf8ffp_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dylib" {...props}></Icon>
