<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aai67211g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aai67211g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-top-line" {...props}></Icon>
