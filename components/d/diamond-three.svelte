<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg1jh-27v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yg1jh-27v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:diamond-three" {...props}></Icon>
