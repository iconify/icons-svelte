<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr6i36bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hr6i36bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-down-gloss" {...props}></Icon>
