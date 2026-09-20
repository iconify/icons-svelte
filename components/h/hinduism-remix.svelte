<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2q2b_7gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i2q2b_7gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hinduism-remix" {...props}></Icon>
