<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hexpvw9fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hexpvw9fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bluetooth-disabled-solid" {...props}></Icon>
