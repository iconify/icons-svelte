<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plq1snb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="plq1snb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:internet-archive" {...props}></Icon>
