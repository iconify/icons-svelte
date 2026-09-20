<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1ggj4blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1ggj4blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-letter-f-filled" {...props}></Icon>
