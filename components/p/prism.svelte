<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-v0owbtv.css';
import '../../css/e/ebu833blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-v0owbtv"/><path class="ebu833blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:prism" {...props}></Icon>
