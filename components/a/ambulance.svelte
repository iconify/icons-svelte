<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zavhcvy1d.css';
import '../../css/l/lwsmj8vpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":24};
const content = `<path class="zavhcvy1d"/><path class="lwsmj8vpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:ambulance" {...props}></Icon>
