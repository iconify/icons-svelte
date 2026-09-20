<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec1c9ybub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec1c9ybub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-confuzed-filled" {...props}></Icon>
