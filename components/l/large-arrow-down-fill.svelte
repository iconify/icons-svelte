<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yho0q7j2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yho0q7j2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-down-fill" {...props}></Icon>
