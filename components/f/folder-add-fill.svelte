<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-j2dobxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-j2dobxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-add-fill" {...props}></Icon>
