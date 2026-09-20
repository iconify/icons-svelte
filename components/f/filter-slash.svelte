<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg6fhmlef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg6fhmlef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:filter-slash" {...props}></Icon>
