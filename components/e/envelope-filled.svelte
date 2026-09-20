<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1xu5s72o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i1xu5s72o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:envelope-filled" {...props}></Icon>
