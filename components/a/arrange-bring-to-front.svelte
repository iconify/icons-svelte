<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiufbeg5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiufbeg5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrange-bring-to-front" {...props}></Icon>
