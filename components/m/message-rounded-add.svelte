<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkhnrobqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dkhnrobqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-rounded-add" {...props}></Icon>
