<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpamm-b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wpamm-b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-arrows-shrink" {...props}></Icon>
