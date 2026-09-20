<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj5wano6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rj5wano6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:copy-2-solid" {...props}></Icon>
