<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocp6qsboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocp6qsboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mug" {...props}></Icon>
