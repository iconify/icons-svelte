<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr2e7hb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jr2e7hb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:departure-time-remix" {...props}></Icon>
