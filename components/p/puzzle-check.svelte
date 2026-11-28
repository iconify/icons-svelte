<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udy-qb4uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udy-qb4uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:puzzle-check" {...props}></Icon>
