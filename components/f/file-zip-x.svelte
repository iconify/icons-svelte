<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfvle8bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfvle8bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-zip-x" {...props}></Icon>
