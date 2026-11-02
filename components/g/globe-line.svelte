<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gngs7_bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gngs7_bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:globe-line" {...props}></Icon>
