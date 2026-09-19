<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8iftzbxv.css';
import '../../css/z/zm26i8bpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s8iftzbxv"/><path class="zm26i8bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:dislike-twotone" {...props}></Icon>
