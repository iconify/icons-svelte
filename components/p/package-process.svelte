<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wghfu3bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wghfu3bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:package-process" {...props}></Icon>
