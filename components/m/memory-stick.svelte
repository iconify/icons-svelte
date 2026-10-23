<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6aqrrb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6aqrrb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:memory-stick" {...props}></Icon>
