<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q22nrovpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q22nrovpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-d8-outline" {...props}></Icon>
