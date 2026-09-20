<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohaf0s28w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohaf0s28w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pdf" {...props}></Icon>
