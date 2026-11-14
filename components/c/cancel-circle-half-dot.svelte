<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asp2-2t9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asp2-2t9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cancel-circle-half-dot" {...props}></Icon>
