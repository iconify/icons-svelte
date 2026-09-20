<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq-pvm52u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="mq-pvm52u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:lightning" {...props}></Icon>
