<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jks7n9fgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="jks7n9fgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:edge" {...props}></Icon>
