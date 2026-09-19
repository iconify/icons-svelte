<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fst7lybqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="fst7lybqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:deletefolder" {...props}></Icon>
