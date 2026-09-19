<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt9uezbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt9uezbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:phone-outcome" {...props}></Icon>
