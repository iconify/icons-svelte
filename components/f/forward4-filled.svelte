<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9qn4wb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9qn4wb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:forward4-filled" {...props}></Icon>
