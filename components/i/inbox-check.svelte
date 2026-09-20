<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qepj9eb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qepj9eb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:inbox-check" {...props}></Icon>
