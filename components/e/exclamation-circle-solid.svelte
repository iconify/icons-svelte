<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw6plybjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jw6plybjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:exclamation-circle-solid" {...props}></Icon>
