<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukhh2zsnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ukhh2zsnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifer-zoom-out-bold" {...props}></Icon>
