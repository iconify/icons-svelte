<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tapjybcoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tapjybcoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:radar" {...props}></Icon>
