<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoou77l6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aoou77l6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:music-check" {...props}></Icon>
