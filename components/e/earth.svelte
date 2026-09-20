<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxswv9z9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fxswv9z9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:earth" {...props}></Icon>
