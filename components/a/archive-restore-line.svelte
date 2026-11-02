<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us4pzjbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us4pzjbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:archive-restore-line" {...props}></Icon>
