<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pths35cza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pths35cza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:remove-male" {...props}></Icon>
