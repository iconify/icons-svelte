<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad1sq0als.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad1sq0als"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:phone-paused-line" {...props}></Icon>
