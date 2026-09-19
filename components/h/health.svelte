<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo92gdcos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo92gdcos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:health" {...props}></Icon>
