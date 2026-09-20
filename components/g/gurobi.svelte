<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csbqcrbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csbqcrbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gurobi" {...props}></Icon>
