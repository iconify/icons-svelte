<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q897uuj-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q897uuj-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radar-2-broken" {...props}></Icon>
