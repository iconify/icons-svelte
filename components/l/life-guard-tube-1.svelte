<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coy96zbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coy96zbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:life-guard-tube-1" {...props}></Icon>
