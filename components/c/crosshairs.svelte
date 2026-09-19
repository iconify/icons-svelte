<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuocq_bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuocq_bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:crosshairs" {...props}></Icon>
