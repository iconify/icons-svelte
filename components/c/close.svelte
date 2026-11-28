<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as5to3b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as5to3b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:close" {...props}></Icon>
