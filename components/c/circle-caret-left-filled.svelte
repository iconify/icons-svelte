<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x47gr45iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x47gr45iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-caret-left-filled" {...props}></Icon>
