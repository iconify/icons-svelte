<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayjkvzbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayjkvzbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:regex-off" {...props}></Icon>
