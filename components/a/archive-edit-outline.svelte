<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b90y7byle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b90y7byle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-edit-outline" {...props}></Icon>
