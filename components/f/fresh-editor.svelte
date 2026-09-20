<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m411hed6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m411hed6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fresh-editor" {...props}></Icon>
