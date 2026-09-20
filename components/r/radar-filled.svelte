<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqkkg5bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqkkg5bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:radar-filled" {...props}></Icon>
