<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlht_y30p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlht_y30p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:camera" {...props}></Icon>
