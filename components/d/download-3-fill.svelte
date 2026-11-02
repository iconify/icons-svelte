<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcvz30b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcvz30b_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:download-3-fill" {...props}></Icon>
