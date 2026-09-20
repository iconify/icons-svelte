<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb-87k45x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb-87k45x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-up-broken" {...props}></Icon>
