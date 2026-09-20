<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g947x_bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g947x_bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:exit-fullscreen" {...props}></Icon>
