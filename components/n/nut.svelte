<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3mrshbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="j3mrshbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:nut" {...props}></Icon>
