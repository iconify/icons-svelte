<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9ye_f-yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x9ye_f-yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bug" {...props}></Icon>
