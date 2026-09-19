<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj7--_fqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj7--_fqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:next-page" {...props}></Icon>
