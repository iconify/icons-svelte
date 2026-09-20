<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obj3babap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="obj3babap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lufthansa-dark" {...props}></Icon>
