<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdx_gpbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hdx_gpbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:plant-in-raised-planter" {...props}></Icon>
