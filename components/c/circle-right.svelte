<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpjh21o_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lpjh21o_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:circle-right" {...props}></Icon>
