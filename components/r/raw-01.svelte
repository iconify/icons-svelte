<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puo9268es.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="puo9268es"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:raw-01" {...props}></Icon>
