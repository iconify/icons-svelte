<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y86xn6bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y86xn6bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dialpad-off" {...props}></Icon>
