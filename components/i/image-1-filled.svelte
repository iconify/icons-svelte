<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpa3fzbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpa3fzbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:image-1-filled" {...props}></Icon>
