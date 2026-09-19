<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilt4b8bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilt4b8bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bolt" {...props}></Icon>
