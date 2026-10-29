<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdt4p5bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdt4p5bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-play" {...props}></Icon>
