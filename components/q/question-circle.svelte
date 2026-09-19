<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2ban2-eb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x2ban2-eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:question-circle" {...props}></Icon>
