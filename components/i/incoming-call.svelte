<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efbhpub7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="efbhpub7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:incoming-call" {...props}></Icon>
