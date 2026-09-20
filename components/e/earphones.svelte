<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezcpi4ljm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ezcpi4ljm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:earphones" {...props}></Icon>
