<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epwa4ib1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="epwa4ib1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:paragraph-right" {...props}></Icon>
