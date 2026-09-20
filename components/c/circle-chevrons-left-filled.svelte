<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfys5y2ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfys5y2ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-chevrons-left-filled" {...props}></Icon>
