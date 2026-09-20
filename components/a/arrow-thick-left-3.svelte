<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlh665i3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlh665i3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-thick-left-3" {...props}></Icon>
