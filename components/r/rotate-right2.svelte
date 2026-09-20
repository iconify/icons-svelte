<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz9ww4b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz9ww4b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:rotate-right2" {...props}></Icon>
