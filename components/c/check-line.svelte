<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asf522r5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asf522r5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:check-line" {...props}></Icon>
