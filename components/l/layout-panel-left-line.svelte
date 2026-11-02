<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg6wwbboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cg6wwbboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-panel-left-line" {...props}></Icon>
