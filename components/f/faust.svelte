<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze24i7f5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":442,"height":512};
const content = `<path class="ze24i7f5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:faust" {...props}></Icon>
