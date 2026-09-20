<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjrt-gnxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjrt-gnxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ai21labs-jamba" {...props}></Icon>
