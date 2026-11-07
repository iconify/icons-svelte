<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odp-njbud.css';
import '../../css/r/rxyy9rljh.css';
import '../../css/q/q5dzxvb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odp-njbud"/><path class="rxyy9rljh"/><path class="q5dzxvb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-left-bold" {...props}></Icon>
