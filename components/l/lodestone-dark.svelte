<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x85s4hwda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x85s4hwda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lodestone-dark" {...props}></Icon>
