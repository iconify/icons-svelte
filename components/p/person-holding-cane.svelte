<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct9hup_mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ct9hup_mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-holding-cane" {...props}></Icon>
