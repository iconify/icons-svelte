<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arfc1ybtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arfc1ybtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clipboard-check" {...props}></Icon>
