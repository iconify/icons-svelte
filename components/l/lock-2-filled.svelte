<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjtqy7uzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jjtqy7uzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:lock-2-filled" {...props}></Icon>
