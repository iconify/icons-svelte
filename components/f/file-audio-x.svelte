<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkxfvs8vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkxfvs8vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-audio-x" {...props}></Icon>
