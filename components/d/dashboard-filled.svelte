<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4xin6b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4xin6b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dashboard-filled" {...props}></Icon>
