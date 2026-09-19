<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mae29i7lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mae29i7lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:paragraph" {...props}></Icon>
