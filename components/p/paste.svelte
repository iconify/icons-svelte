<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-294_b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l-294_b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:paste" {...props}></Icon>
