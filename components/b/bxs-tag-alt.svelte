<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7v4qmbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7v4qmbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-tag-alt" {...props}></Icon>
