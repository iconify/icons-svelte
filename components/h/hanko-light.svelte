<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqr77ac-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqr77ac-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hanko-light" {...props}></Icon>
