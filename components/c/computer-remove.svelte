<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jug5mab_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jug5mab_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:computer-remove" {...props}></Icon>
