<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4d10v-zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="j4d10v-zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:flag-1" {...props}></Icon>
