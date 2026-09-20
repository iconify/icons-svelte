<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgr11cbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgr11cbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-47-small" {...props}></Icon>
