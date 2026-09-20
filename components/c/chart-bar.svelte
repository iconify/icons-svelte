<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0m8o8bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0m8o8bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:chart-bar" {...props}></Icon>
