<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh7e7ubci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh7e7ubci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-minus-line" {...props}></Icon>
