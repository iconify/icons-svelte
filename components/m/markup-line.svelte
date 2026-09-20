<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osmryt6ri.css';
import '../../css/n/nzqrsacsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osmryt6ri"/><path class="nzqrsacsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:markup-line" {...props}></Icon>
