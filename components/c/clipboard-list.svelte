<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9vv3jxuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="h9vv3jxuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:clipboard-list" {...props}></Icon>
