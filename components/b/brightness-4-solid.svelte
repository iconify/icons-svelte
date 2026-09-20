<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr8pc26yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lr8pc26yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:brightness-4-solid" {...props}></Icon>
