<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yei82dpsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yei82dpsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:diagram-tree" {...props}></Icon>
