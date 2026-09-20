<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2jwvtb7p.css';
import '../../css/e/eimq_kjxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2jwvtb7p"/><path class="eimq_kjxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:archive-box" {...props}></Icon>
