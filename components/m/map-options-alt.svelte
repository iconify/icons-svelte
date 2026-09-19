<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm_6fobjp.css';
import '../../css/h/h1ytemzns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="hm_6fobjp"/><path class="h1ytemzns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-options-alt" {...props}></Icon>
