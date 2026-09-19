<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7rwn8boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h7rwn8boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:caret-up-circle" {...props}></Icon>
