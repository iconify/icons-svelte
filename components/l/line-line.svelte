<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyc-bvbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyc-bvbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:line-line" {...props}></Icon>
