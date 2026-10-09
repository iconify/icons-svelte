<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk9klbblz.css';
import '../../css/j/j8rsm4b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jk9klbblz"/><path class="j8rsm4b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:inbox-20" {...props}></Icon>
