<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8_9n6byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8_9n6byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arrow-alt-ldown-alt" {...props}></Icon>
