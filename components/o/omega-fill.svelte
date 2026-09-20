<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekx4z0myv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekx4z0myv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:omega-fill" {...props}></Icon>
