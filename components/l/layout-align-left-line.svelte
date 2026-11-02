<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3du-24zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3du-24zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-align-left-line" {...props}></Icon>
