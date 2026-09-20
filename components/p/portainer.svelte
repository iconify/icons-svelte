<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1_x_9bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1_x_9bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:portainer" {...props}></Icon>
