<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytwfhhbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ytwfhhbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:help-center-26" {...props}></Icon>
