<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztrm5fe8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztrm5fe8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:original-size-filled" {...props}></Icon>
