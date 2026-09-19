<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bloqio82m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bloqio82m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:arrows-compress" {...props}></Icon>
