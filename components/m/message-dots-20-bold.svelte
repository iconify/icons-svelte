<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajyu9s76q.css';
import '../../css/c/cbj0tbbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ajyu9s76q"/><path class="cbj0tbbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-dots-20-bold" {...props}></Icon>
