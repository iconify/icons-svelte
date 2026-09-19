<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlvth03fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="vlvth03fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:archive-square" {...props}></Icon>
