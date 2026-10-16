<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlfukpbru.css';
import '../../css/s/sgrfz4b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jlfukpbru"/><path class="sgrfz4b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flowchart-20" {...props}></Icon>
