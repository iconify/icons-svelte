<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj6r4aboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="oj6r4aboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:pubpeer-square" {...props}></Icon>
