<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an6_-bb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="an6_-bb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:factory-reset" {...props}></Icon>
