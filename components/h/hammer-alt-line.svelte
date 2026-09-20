<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jekm3z_ba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jekm3z_ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:hammer-alt-line" {...props}></Icon>
