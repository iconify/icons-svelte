<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd7cgg0ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="dd7cgg0ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:headphone" {...props}></Icon>
