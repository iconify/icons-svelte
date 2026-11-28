<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg_s41kyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg_s41kyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-x" {...props}></Icon>
