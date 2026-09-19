<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr8-a7llk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="sr8-a7llk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:compass" {...props}></Icon>
