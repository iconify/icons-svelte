<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-1l6vtvu.css';
import '../../css/z/zdawap23x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-1l6vtvu"/><path class="zdawap23x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pill-bold-duotone" {...props}></Icon>
