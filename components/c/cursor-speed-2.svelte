<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9hl6jg0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9hl6jg0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:cursor-speed-2" {...props}></Icon>
