<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi0bogb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="vi0bogb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:peak-10" {...props}></Icon>
