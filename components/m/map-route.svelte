<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iknee7b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iknee7b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-route" {...props}></Icon>
