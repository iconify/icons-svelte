<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6dwxwbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f6dwxwbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:openbsd-alt" {...props}></Icon>
