<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh_0adbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="wh_0adbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:industry-11" {...props}></Icon>
