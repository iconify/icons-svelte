<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj89p6enm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yj89p6enm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:code-square-solid" {...props}></Icon>
