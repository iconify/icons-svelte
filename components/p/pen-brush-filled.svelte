<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs47u9j4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs47u9j4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:pen-brush-filled" {...props}></Icon>
