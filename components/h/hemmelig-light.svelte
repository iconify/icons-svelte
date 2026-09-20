<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_63gm0nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_63gm0nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hemmelig-light" {...props}></Icon>
