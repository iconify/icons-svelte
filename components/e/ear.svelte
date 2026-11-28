<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7nz21b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7nz21b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ear" {...props}></Icon>
