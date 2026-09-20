<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-jhqhb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-jhqhb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-ppt-fill" {...props}></Icon>
