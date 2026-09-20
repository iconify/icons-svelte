<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8qa1w28i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="g8qa1w28i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:push-up" {...props}></Icon>
