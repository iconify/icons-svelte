<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xewd8ubff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":424,"height":512};
const content = `<path class="xewd8ubff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:prisma" {...props}></Icon>
