<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw-ztc7eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw-ztc7eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:receipt2-filled" {...props}></Icon>
