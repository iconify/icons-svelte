<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbmg-z4wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":24};
const content = `<path class="mbmg-z4wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:night-alt-cloudy" {...props}></Icon>
