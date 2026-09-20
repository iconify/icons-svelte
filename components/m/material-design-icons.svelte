<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhd69yzkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhd69yzkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:material-design-icons" {...props}></Icon>
