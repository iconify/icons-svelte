<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp5lk3b5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="kp5lk3b5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:panty" {...props}></Icon>
