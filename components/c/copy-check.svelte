<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grhdxjbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grhdxjbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:copy-check" {...props}></Icon>
