<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajyu9s76q.css';
import '../../css/p/porjtp6kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ajyu9s76q"/><path class="porjtp6kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-alert-20-bold" {...props}></Icon>
