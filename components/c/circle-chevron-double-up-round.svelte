<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdbc1eb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdbc1eb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-chevron-double-up-round" {...props}></Icon>
