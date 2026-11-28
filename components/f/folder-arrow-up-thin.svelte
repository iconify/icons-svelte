<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy18rac_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="sy18rac_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:folder-arrow-up-thin" {...props}></Icon>
