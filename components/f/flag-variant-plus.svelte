<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6zmu34di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6zmu34di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-variant-plus" {...props}></Icon>
