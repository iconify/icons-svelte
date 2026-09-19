<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riwpk_voa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":24};
const content = `<path class="riwpk_voa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:jekyll" {...props}></Icon>
