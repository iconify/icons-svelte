<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6whuwz5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b6whuwz5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:phone-filled" {...props}></Icon>
