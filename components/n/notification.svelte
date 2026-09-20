<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuolribpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nuolribpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:notification" {...props}></Icon>
