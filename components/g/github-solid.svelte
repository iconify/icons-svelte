<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdy6r9b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdy6r9b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:github-solid" {...props}></Icon>
