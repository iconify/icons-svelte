<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axs8swbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axs8swbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:lock-unlock-4-bold" {...props}></Icon>
