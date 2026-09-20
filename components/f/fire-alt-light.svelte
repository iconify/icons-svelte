<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffnqqkbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffnqqkbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:fire-alt-light" {...props}></Icon>
