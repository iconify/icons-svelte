<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vosp1ja8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vosp1ja8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:close-square-fill" {...props}></Icon>
