<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxk5kjbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxk5kjbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-right-2-fill" {...props}></Icon>
