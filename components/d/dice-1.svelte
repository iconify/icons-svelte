<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3ce-xdtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3ce-xdtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dice-1" {...props}></Icon>
