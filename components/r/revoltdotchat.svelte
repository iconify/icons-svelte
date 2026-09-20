<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enc6m9bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enc6m9bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:revoltdotchat" {...props}></Icon>
