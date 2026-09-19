<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icsu46bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":512};
const content = `<path class="icsu46bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:grip-lines-vertical" {...props}></Icon>
