<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buc-j7b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="buc-j7b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:give-star" {...props}></Icon>
