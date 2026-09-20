<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg0jpcchu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg0jpcchu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:maximize4-filled" {...props}></Icon>
