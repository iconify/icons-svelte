<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx-ibsb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx-ibsb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:a-arrow-down" {...props}></Icon>
