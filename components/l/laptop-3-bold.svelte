<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_78m3epb.css';
import '../../css/c/cq7nq2bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_78m3epb"/><path class="cq7nq2bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:laptop-3-bold" {...props}></Icon>
