<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7yyxubhq.css';
import '../../css/d/d0kcjfbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z7yyxubhq"/><path class="d0kcjfbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:meter-cabinet-20" {...props}></Icon>
