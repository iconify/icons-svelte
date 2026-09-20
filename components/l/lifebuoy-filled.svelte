<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiq5p1cvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wiq5p1cvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lifebuoy-filled" {...props}></Icon>
