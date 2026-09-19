<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6q6ugetu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":480,"height":448};
const content = `<path class="n6q6ugetu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:quote" {...props}></Icon>
