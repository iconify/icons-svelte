<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scjpqqb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scjpqqb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-b-filled" {...props}></Icon>
