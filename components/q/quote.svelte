<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xokkt-ppm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xokkt-ppm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:quote" {...props}></Icon>
