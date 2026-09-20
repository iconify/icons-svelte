<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq4i1lqpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq4i1lqpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:authentik" {...props}></Icon>
