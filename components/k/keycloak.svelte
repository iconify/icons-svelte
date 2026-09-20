<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-9l2s4jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-9l2s4jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:keycloak" {...props}></Icon>
