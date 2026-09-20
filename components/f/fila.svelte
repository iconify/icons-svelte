<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms_7ga3th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms_7ga3th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fila" {...props}></Icon>
