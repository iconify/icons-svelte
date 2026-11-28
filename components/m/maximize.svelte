<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz0r-v44t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz0r-v44t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:maximize" {...props}></Icon>
