<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4uc9vb-s.css';
import '../../css/u/u7e-84bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":19,"height":24};
const content = `<path class="g4uc9vb-s"/><path class="u7e-84bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:hot-air-balloon" {...props}></Icon>
