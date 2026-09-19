<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m09q97s_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="m09q97s_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:blogger-rect" {...props}></Icon>
