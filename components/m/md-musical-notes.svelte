<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6zrwub-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i6zrwub-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-musical-notes" {...props}></Icon>
