<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg-yorbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sg-yorbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:plus-circle-o" {...props}></Icon>
