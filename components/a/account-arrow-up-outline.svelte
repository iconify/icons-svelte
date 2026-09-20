<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c47r4ib7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c47r4ib7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-arrow-up-outline" {...props}></Icon>
