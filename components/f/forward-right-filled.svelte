<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5lxj0zxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5lxj0zxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:forward-right-filled" {...props}></Icon>
