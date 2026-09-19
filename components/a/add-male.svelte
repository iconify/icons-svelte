<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxw36h-hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxw36h-hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:add-male" {...props}></Icon>
