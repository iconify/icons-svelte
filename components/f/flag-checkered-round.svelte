<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia8h-s6qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia8h-s6qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flag-checkered-round" {...props}></Icon>
