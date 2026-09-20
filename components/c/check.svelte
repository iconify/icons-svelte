<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw3rb4-fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw3rb4-fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:check" {...props}></Icon>
