<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1p332b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1p332b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-q-circle-outline" {...props}></Icon>
