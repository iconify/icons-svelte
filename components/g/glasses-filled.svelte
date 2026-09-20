<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/metcehf7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="metcehf7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:glasses-filled" {...props}></Icon>
