<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckj9cdcfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckj9cdcfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:beta" {...props}></Icon>
