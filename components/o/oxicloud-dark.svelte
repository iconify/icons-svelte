<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjcdi0bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gjcdi0bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oxicloud-dark" {...props}></Icon>
