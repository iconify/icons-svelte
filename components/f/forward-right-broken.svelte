<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3kl957aa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3kl957aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forward-right-broken" {...props}></Icon>
