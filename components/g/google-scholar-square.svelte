<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aptqpabig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="aptqpabig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:google-scholar-square" {...props}></Icon>
