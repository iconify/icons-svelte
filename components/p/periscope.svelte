<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gac6sofbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":19,"height":24};
const content = `<path class="gac6sofbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:periscope" {...props}></Icon>
