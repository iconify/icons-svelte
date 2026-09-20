<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slpu4qtxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slpu4qtxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-wind" {...props}></Icon>
