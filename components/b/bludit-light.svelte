<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5xvncr9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i5xvncr9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bludit-light" {...props}></Icon>
