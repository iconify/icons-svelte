<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9l0g5yva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9l0g5yva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:briefcase-filled" {...props}></Icon>
