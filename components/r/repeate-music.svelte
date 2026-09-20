<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5zqy3b9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5zqy3b9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:repeate-music" {...props}></Icon>
