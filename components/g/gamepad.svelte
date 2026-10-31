<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do06-f15x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do06-f15x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gamepad" {...props}></Icon>
