<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnr3be0jq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnr3be0jq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:codeflicker" {...props}></Icon>
