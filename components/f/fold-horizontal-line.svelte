<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6eo6ewzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6eo6ewzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fold-horizontal-line" {...props}></Icon>
