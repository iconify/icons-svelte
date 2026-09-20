<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnvmww__d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnvmww__d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pronounsdotpage" {...props}></Icon>
