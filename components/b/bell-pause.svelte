<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v22x25v2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v22x25v2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-pause" {...props}></Icon>
