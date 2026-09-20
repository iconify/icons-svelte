<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uurlk9r4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uurlk9r4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:file-line" {...props}></Icon>
