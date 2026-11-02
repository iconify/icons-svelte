<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw33au4cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lw33au4cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:first-aid-kit-line" {...props}></Icon>
