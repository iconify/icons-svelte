<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjiax_43i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rjiax_43i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hill-conquest" {...props}></Icon>
