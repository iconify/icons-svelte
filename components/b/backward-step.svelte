<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cutf4dd8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cutf4dd8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:backward-step" {...props}></Icon>
