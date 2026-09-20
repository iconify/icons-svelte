<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v67vhyu1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v67vhyu1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chevron-up-bar-small" {...props}></Icon>
