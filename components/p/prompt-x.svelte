<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqlb4602y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqlb4602y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:prompt-x" {...props}></Icon>
