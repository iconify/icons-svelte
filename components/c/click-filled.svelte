<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y279e5bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y279e5bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:click-filled" {...props}></Icon>
