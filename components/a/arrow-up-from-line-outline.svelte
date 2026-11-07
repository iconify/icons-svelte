<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2f7hu3hn.css';
import '../../css/v/vh0_98nmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2f7hu3hn"/><path class="vh0_98nmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-up-from-line-outline" {...props}></Icon>
