<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsop0413d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsop0413d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag2-filled" {...props}></Icon>
