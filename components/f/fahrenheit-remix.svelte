<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjkuf-brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bjkuf-brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:fahrenheit-remix" {...props}></Icon>
