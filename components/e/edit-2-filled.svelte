<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3eym7b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3eym7b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:edit-2-filled" {...props}></Icon>
