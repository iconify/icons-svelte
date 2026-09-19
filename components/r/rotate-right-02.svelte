<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2-h72ynu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2-h72ynu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-right-02" {...props}></Icon>
