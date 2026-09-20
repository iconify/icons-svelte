<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6s5kw3-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6s5kw3-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:car-fan-1" {...props}></Icon>
