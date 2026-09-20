<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw9p3ab6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw9p3ab6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bell-filled" {...props}></Icon>
