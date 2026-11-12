<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaonzxg2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iaonzxg2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anki-dark" {...props}></Icon>
