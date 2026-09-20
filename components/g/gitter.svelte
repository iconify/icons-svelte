<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ual9cq7_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ual9cq7_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gitter" {...props}></Icon>
