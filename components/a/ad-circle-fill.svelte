<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz-gk04le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz-gk04le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ad-circle-fill" {...props}></Icon>
