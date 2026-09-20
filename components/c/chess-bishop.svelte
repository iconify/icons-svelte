<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi89x8t3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi89x8t3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chess-bishop" {...props}></Icon>
