<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olqplchgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olqplchgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:progress-25-line" {...props}></Icon>
