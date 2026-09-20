<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzj3igptw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rzj3igptw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:radar-filled" {...props}></Icon>
