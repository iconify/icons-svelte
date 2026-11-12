<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icu7kjy8b.css';
import '../../css/t/tncgtrlau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="icu7kjy8b"/><path class="tncgtrlau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:android-auto-dark" {...props}></Icon>
