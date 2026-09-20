<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqns7mwxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aqns7mwxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lululemon-dark" {...props}></Icon>
