<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiqpp9k5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiqpp9k5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:quote-left-line" {...props}></Icon>
