<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7e5qwp0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7e5qwp0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-layout-filled" {...props}></Icon>
