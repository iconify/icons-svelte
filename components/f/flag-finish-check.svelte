<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9oeji4xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9oeji4xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:flag-finish-check" {...props}></Icon>
