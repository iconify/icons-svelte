<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srcqntbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srcqntbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chair-2-bold" {...props}></Icon>
