<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7oao_qjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7oao_qjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dts-x" {...props}></Icon>
