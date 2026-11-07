<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtjzwnbwv.css';
import '../../css/d/dbws_7b9j.css';
import '../../css/l/lyi1fbbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtjzwnbwv"/><path class="dbws_7b9j"/><path class="lyi1fbbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-bold" {...props}></Icon>
