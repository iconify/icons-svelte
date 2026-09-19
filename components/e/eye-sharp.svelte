<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shexgfo6g.css';
import '../../css/w/wsjn089ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="shexgfo6g"/><path class="wsjn089ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:eye-sharp" {...props}></Icon>
