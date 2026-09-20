<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qul541b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qul541b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:help-circle-filled" {...props}></Icon>
