<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaz5m1bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jaz5m1bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:quote-right" {...props}></Icon>
