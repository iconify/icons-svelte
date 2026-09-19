<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr5kxzb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jr5kxzb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:face-smile-wink" {...props}></Icon>
