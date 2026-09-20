<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do1c-8sjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="do1c-8sjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:poweroff" {...props}></Icon>
