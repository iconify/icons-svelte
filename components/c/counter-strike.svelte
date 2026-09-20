<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv024--aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv024--aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:counter-strike" {...props}></Icon>
