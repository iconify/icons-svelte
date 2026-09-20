<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtj_33k3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtj_33k3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:neo4j" {...props}></Icon>
