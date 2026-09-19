<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzqkn_xju.css';
import '../../css/q/q-on95byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzqkn_xju"/><path class="q-on95byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:deno" {...props}></Icon>
