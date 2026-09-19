<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlb_rob2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qlb_rob2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:do-undo-fill" {...props}></Icon>
