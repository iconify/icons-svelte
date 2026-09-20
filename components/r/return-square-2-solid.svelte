<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8pc8-bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h8pc8-bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:return-square-2-solid" {...props}></Icon>
