<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7gmyhb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="x7gmyhb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:preregistered-de-square" {...props}></Icon>
