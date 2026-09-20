<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvx85gb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvx85gb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clipboard-x-filled" {...props}></Icon>
