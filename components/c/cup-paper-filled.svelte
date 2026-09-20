<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obk1lubzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obk1lubzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cup-paper-filled" {...props}></Icon>
