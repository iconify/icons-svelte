<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7n23_boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m7n23_boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chevron-left-small" {...props}></Icon>
