<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxt81ccuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gxt81ccuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ipcontrol" {...props}></Icon>
