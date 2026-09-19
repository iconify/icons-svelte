<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcsy3isws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xcsy3isws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:alarm-clock" {...props}></Icon>
