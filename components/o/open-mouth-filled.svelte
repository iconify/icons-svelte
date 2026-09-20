<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/typ9t6dud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="typ9t6dud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:open-mouth-filled" {...props}></Icon>
