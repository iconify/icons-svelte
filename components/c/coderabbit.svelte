<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry5r86ipa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry5r86ipa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:coderabbit" {...props}></Icon>
