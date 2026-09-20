<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da6d5ejeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="da6d5ejeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:arrow-diagonal-top-right" {...props}></Icon>
