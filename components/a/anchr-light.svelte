<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhiq11z0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jhiq11z0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anchr-light" {...props}></Icon>
