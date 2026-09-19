<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rne-a9b6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rne-a9b6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:battery" {...props}></Icon>
