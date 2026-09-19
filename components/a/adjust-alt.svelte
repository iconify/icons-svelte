<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqmzj2bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqmzj2bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:adjust-alt" {...props}></Icon>
