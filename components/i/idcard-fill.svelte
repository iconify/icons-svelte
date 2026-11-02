<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwfn7648c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwfn7648c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:idcard-fill" {...props}></Icon>
