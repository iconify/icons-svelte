<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5l8oircu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5l8oircu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hand-pointer" {...props}></Icon>
