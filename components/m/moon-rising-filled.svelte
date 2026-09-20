<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6i3jx7ty.css';
import '../../css/c/c88l3cbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6i3jx7ty"/><path class="c88l3cbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:moon-rising-filled" {...props}></Icon>
