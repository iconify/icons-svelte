<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhwsd0bam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":758,"height":666};
const content = `<path class="qhwsd0bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:edit" {...props}></Icon>
