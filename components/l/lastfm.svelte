<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_unyib1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":994.95,"height":1000};
const content = `<path class="q_unyib1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:lastfm" {...props}></Icon>
