<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q90a30i4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q90a30i4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-share-alt" {...props}></Icon>
