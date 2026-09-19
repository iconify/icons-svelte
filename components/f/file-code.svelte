<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lobsk4bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lobsk4bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-code" {...props}></Icon>
