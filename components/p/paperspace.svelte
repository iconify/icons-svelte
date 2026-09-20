<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etig-_o3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etig-_o3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:paperspace" {...props}></Icon>
