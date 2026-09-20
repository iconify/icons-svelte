<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbiia3cfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbiia3cfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:crown" {...props}></Icon>
