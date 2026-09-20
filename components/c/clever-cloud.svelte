<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meydrebwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="meydrebwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:clever-cloud" {...props}></Icon>
