<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucae7xdov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucae7xdov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-vertical-distribute-start-line" {...props}></Icon>
