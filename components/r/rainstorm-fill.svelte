<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abgj25bzr.css';
import '../../css/a/almf4_bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abgj25bzr"/><path class="almf4_bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rainstorm-fill" {...props}></Icon>
