<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm69rlbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="nm69rlbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:createnew" {...props}></Icon>
