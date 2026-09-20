<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz7ph1gyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="mz7ph1gyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:highlighter-1" {...props}></Icon>
