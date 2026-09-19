<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvca9t96l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvca9t96l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:quote-alt-left" {...props}></Icon>
