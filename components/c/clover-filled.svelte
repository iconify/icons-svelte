<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k84dp8bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k84dp8bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clover-filled" {...props}></Icon>
