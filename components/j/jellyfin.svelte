<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2ajhqn1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ajhqn1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jellyfin" {...props}></Icon>
