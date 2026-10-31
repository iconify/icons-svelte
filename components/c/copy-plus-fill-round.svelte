<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/taf--bs9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="taf--bs9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:copy-plus-fill-round" {...props}></Icon>
