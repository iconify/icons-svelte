<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yobm0iblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yobm0iblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dice-d6" {...props}></Icon>
