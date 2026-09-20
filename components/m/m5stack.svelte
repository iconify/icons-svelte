<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj96m5m8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj96m5m8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:m5stack" {...props}></Icon>
