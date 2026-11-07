<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it-6mlbhr.css';
import '../../css/b/bckx04b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it-6mlbhr"/><path clip-rule="evenodd" class="bckx04b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:backpack-outline" {...props}></Icon>
