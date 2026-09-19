<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4plitbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d4plitbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:blitzbasic" {...props}></Icon>
