<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmjy-5bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="qmjy-5bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:drums" {...props}></Icon>
