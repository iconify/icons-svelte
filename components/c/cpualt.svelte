<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si8w2mlyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="si8w2mlyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cpualt" {...props}></Icon>
