<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-h-nlbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-h-nlbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:record-audio" {...props}></Icon>
