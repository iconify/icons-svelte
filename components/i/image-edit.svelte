<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqk_9joly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqk_9joly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:image-edit" {...props}></Icon>
