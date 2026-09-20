<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0anb3hgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o0anb3hgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dropout-light" {...props}></Icon>
