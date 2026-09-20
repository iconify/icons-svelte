<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeceec92t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aeceec92t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pier" {...props}></Icon>
