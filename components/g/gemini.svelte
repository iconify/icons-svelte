<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o37hg4b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o37hg4b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:gemini" {...props}></Icon>
