<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf_7njbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="gf_7njbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:male" {...props}></Icon>
