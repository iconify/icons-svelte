<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcwo0ib5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jcwo0ib5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adguard-home-dark" {...props}></Icon>
