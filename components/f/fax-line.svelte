<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quzx1ub2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quzx1ub2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fax-line" {...props}></Icon>
