<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfz3p5diu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kfz3p5diu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jula-light" {...props}></Icon>
