<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2k7zsk0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2k7zsk0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-down" {...props}></Icon>
