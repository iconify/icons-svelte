<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axque105x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="axque105x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:blogger" {...props}></Icon>
