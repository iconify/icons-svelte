<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g66jyg1bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g66jyg1bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:atm" {...props}></Icon>
