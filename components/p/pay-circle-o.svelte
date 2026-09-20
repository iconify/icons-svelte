<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kakrw9-lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kakrw9-lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:pay-circle-o" {...props}></Icon>
