<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewfk1xync.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewfk1xync"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:lamp-fill" {...props}></Icon>
