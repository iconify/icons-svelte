<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu8eogszi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="qu8eogszi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:remove" {...props}></Icon>
