<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spopz0byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spopz0byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:content-ink-pen-write-bold" {...props}></Icon>
