<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if1fl5uuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="if1fl5uuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:headphone-1" {...props}></Icon>
