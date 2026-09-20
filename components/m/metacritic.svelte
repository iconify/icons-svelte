<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy9xttbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy9xttbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:metacritic" {...props}></Icon>
