<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw5x7wlrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aw5x7wlrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:ban-outline" {...props}></Icon>
