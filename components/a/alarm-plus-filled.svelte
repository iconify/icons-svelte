<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8nihrbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q8nihrbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alarm-plus-filled" {...props}></Icon>
