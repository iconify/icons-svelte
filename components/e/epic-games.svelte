<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnw_dv-nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnw_dv-nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:epic-games" {...props}></Icon>
