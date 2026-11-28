<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqzfwhb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqzfwhb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:more-horizontal" {...props}></Icon>
