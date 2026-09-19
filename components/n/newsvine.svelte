<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqzm5abuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":488};
const content = `<path class="zqzm5abuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:newsvine" {...props}></Icon>
