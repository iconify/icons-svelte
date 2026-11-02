<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhhgsxamz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhhgsxamz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-unknown-line" {...props}></Icon>
