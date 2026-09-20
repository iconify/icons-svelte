<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-zau8bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h-zau8bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portabase-dark" {...props}></Icon>
