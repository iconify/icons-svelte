<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qydrce42n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qydrce42n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:github-fill" {...props}></Icon>
