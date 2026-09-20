<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i44r3pb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i44r3pb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hyperpipe-light" {...props}></Icon>
