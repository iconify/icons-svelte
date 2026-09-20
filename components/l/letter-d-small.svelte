<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2-v6rp2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2-v6rp2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-d-small" {...props}></Icon>
