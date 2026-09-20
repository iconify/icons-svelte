<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igwza9xzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="igwza9xzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pied-piper-alt" {...props}></Icon>
