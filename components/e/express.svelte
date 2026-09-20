<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo0febkba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo0febkba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:express" {...props}></Icon>
