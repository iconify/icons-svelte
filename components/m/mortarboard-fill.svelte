<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1cd53nrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1cd53nrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mortarboard-fill" {...props}></Icon>
