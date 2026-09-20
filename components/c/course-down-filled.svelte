<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aibd18w3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aibd18w3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:course-down-filled" {...props}></Icon>
