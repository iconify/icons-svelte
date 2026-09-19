<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7n05ph0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="k7n05ph0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:famale" {...props}></Icon>
