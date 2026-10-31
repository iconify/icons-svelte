<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc2nu2bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc2nu2bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-down-gloss" {...props}></Icon>
