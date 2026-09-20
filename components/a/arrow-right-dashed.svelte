<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuleku48b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuleku48b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-right-dashed" {...props}></Icon>
