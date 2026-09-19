<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkeboabeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="fkeboabeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:clipboard-user" {...props}></Icon>
