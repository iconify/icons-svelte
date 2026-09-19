<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lckii8bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lckii8bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-gitlab" {...props}></Icon>
