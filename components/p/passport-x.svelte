<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8d9ur5rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8d9ur5rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:passport-x" {...props}></Icon>
