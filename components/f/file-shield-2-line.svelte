<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkql_rbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkql_rbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-shield-2-line" {...props}></Icon>
