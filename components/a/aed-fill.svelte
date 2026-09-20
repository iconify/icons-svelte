<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et9hudb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="et9hudb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:aed-fill" {...props}></Icon>
