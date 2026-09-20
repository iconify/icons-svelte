<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wclhac05w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wclhac05w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-minus-filled" {...props}></Icon>
