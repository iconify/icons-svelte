<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oulbc4bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oulbc4bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cell-signal-1" {...props}></Icon>
