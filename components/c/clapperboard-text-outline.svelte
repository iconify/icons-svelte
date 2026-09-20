<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx-6mabls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jx-6mabls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clapperboard-text-outline" {...props}></Icon>
