<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjfn-njpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xjfn-njpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chess-knight-solid" {...props}></Icon>
