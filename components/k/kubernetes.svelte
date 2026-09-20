<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ganpgob_x.css';
import '../../css/n/nh_1xf49f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":722.8,"height":702};
const content = `<path class="ganpgob_x"/><path class="nh_1xf49f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kubernetes" {...props}></Icon>
