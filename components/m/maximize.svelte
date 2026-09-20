<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdk9i9par.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdk9i9par"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:maximize" {...props}></Icon>
