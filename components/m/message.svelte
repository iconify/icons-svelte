<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2b9f33ui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2b9f33ui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message" {...props}></Icon>
