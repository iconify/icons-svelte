<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv-43281c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv-43281c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nuki" {...props}></Icon>
