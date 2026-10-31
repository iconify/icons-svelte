<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhym1fszd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhym1fszd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-help-round" {...props}></Icon>
