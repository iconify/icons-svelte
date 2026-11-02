<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_1vc6bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_1vc6bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copper-coin-fill" {...props}></Icon>
