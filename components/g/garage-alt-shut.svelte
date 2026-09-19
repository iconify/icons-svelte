<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr_tvqbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr_tvqbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:garage-alt-shut" {...props}></Icon>
