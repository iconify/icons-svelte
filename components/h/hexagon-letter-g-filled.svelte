<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am1tq7v-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am1tq7v-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-g-filled" {...props}></Icon>
