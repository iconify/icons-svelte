<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7ze7-tqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n7ze7-tqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:asciinema-dark" {...props}></Icon>
