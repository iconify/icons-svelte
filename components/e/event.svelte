<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp7lv3bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lp7lv3bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:event" {...props}></Icon>
