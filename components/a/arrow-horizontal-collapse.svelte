<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6n6gll-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6n6gll-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-horizontal-collapse" {...props}></Icon>
