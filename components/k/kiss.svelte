<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sez7-guzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sez7-guzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:kiss" {...props}></Icon>
