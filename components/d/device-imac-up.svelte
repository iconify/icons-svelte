<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqjz04cwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqjz04cwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-up" {...props}></Icon>
