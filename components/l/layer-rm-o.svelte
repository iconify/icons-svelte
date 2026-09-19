<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk3cacbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zk3cacbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-rm-o" {...props}></Icon>
