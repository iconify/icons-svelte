<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecjx1yg4j.css';
import '../../css/l/l6k0rd2qb.css';
import '../../css/g/gzcgyebif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ecjx1yg4j"/><path class="l6k0rd2qb"/><path class="gzcgyebif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mop-20" {...props}></Icon>
