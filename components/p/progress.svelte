<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxq30-b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxq30-b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:progress" {...props}></Icon>
