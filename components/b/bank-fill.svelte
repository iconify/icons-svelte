<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f13g02hns.css';
import '../../css/y/y_xfi-b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f13g02hns"/><path class="y_xfi-b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bank-fill" {...props}></Icon>
