<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql-w3z2ta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ql-w3z2ta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:iron-solid" {...props}></Icon>
