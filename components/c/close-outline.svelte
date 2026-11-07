<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbgidvbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbgidvbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:close-outline" {...props}></Icon>
