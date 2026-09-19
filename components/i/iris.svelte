<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6yqyc8aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6yqyc8aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:iris" {...props}></Icon>
