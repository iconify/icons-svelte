<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxyf8dbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="hxyf8dbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fans" {...props}></Icon>
