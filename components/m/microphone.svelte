<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofmw9kbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofmw9kbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:microphone" {...props}></Icon>
