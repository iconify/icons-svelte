<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nob8wmdcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nob8wmdcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:monitor-stop-line" {...props}></Icon>
