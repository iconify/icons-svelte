<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkrn0cc1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkrn0cc1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pencil-off" {...props}></Icon>
