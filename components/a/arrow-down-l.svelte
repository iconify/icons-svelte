<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q386gwb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q386gwb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:arrow-down-l" {...props}></Icon>
