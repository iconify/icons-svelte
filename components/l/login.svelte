<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apmn47bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="apmn47bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:login" {...props}></Icon>
