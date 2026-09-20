<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fra1twdzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="fra1twdzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:envelope" {...props}></Icon>
