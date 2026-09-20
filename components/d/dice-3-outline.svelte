<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1u0azxay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1u0azxay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-3-outline" {...props}></Icon>
