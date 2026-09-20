<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryzr5jw8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryzr5jw8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bath-filled" {...props}></Icon>
