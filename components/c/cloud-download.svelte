<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs6nzj33o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs6nzj33o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:cloud-download" {...props}></Icon>
