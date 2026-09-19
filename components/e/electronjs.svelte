<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn0-sbcys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="pn0-sbcys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:electronjs" {...props}></Icon>
