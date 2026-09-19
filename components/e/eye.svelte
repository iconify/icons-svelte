<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shexgfo6g.css';
import '../../css/o/oin-52btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="shexgfo6g"/><path class="oin-52btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:eye" {...props}></Icon>
