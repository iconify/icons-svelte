<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md_2q2xyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="md_2q2xyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-reload-horizontal-1-flat" {...props}></Icon>
