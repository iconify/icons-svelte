<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugcocacgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugcocacgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right-filled" {...props}></Icon>
