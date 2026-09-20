<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz--5rbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz--5rbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bedrock-aws" {...props}></Icon>
