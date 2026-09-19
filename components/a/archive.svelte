<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka3_2sueq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ka3_2sueq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:archive" {...props}></Icon>
