<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc1zkebew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc1zkebew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mantine" {...props}></Icon>
