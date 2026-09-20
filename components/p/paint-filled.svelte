<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5_26y1bs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5_26y1bs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:paint-filled" {...props}></Icon>
