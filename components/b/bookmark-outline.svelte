<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxlp5qvgf.css';
import '../../css/o/ojf0j38zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxlp5qvgf"/><path clip-rule="evenodd" class="ojf0j38zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-outline" {...props}></Icon>
