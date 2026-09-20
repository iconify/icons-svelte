<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_0m1je2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_0m1je2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pen-writing2-filled" {...props}></Icon>
