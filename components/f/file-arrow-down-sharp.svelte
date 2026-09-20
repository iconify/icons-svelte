<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg5u9m4to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg5u9m4to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-arrow-down-sharp" {...props}></Icon>
