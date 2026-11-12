<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi-oj1bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hi-oj1bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:glpi-dark" {...props}></Icon>
