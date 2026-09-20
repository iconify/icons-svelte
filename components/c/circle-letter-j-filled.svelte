<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7v44bcrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7v44bcrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-j-filled" {...props}></Icon>
