<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vocuwk81g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vocuwk81g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:info-square-rounded-filled" {...props}></Icon>
