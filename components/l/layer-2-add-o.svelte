<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuwzagbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="yuwzagbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-2-add-o" {...props}></Icon>
