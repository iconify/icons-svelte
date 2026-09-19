<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t59wq0bcq.css';
import '../../css/e/e71w-2bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t59wq0bcq"/><path class="e71w-2bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:picture-in-picture-close" {...props}></Icon>
