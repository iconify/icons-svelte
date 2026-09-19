<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eum4rlqcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eum4rlqcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:chapter-previous" {...props}></Icon>
