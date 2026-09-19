<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jla2z_f0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jla2z_f0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:remove-selection" {...props}></Icon>
