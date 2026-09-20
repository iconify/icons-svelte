<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lurx8abhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lurx8abhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:delete-1-filled" {...props}></Icon>
