<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzzh1ommd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qzzh1ommd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-detect-duotone" {...props}></Icon>
