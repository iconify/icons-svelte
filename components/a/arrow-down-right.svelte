<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjic6qb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjic6qb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:arrow-down-right" {...props}></Icon>
