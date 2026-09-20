<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry98j6beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry98j6beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:list" {...props}></Icon>
