<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0iivbcas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0iivbcas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:binoculars-filled" {...props}></Icon>
