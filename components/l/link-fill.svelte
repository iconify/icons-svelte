<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-96895gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-96895gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:link-fill" {...props}></Icon>
