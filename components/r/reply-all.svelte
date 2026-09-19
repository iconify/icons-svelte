<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j549m5b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j549m5b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:reply-all" {...props}></Icon>
