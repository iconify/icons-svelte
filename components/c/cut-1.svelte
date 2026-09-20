<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plumexbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plumexbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cut-1" {...props}></Icon>
