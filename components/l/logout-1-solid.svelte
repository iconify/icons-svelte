<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hltb_3h3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hltb_3h3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:logout-1-solid" {...props}></Icon>
