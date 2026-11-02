<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e97y7kbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e97y7kbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fax-line" {...props}></Icon>
