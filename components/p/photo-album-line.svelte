<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5456z5rt.css';
import '../../css/v/v5gc3bcuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5456z5rt"/><path class="v5gc3bcuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:photo-album-line" {...props}></Icon>
