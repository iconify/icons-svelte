<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oen4v5bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="oen4v5bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:feedly" {...props}></Icon>
