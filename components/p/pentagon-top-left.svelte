<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fijs2gb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fijs2gb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:pentagon-top-left" {...props}></Icon>
