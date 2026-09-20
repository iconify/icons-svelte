<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eddavmbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eddavmbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-drop-down-fill" {...props}></Icon>
