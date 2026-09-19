<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9oalu6-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9oalu6-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:happy-beaming" {...props}></Icon>
