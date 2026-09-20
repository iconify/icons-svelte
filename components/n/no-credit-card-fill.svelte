<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/narv8ub5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="narv8ub5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:no-credit-card-fill" {...props}></Icon>
