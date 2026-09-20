<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zad99_9ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zad99_9ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:npr-one-dark" {...props}></Icon>
