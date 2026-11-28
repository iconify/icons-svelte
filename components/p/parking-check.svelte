<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw92ltm6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw92ltm6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:parking-check" {...props}></Icon>
