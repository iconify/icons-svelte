<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvc-k2bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvc-k2bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:check-thin" {...props}></Icon>
