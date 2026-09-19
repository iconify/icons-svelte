<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osbn5umaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<path class="osbn5umaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:area-chart" {...props}></Icon>
