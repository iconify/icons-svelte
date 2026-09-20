<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y55np039p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y55np039p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:pause" {...props}></Icon>
