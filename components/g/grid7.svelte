<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx0z5_a3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx0z5_a3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid7" {...props}></Icon>
