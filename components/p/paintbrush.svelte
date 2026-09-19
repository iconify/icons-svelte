<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hss7tib0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hss7tib0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:paintbrush" {...props}></Icon>
