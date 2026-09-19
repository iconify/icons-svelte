<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwe_a9b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwe_a9b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:kayo" {...props}></Icon>
