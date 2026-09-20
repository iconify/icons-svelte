<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0wz7wgoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v0wz7wgoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:reorder" {...props}></Icon>
