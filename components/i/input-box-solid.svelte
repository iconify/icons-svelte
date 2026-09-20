<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp5wc9bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cp5wc9bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:input-box-solid" {...props}></Icon>
