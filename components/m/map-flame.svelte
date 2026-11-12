<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-jn8abpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-jn8abpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-flame" {...props}></Icon>
