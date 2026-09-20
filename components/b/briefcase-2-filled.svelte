<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqzn08bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqzn08bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:briefcase-2-filled" {...props}></Icon>
