<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2-_2ac-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2-_2ac-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-center-two-tone" {...props}></Icon>
