<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jps-cbb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jps-cbb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:bell-off" {...props}></Icon>
