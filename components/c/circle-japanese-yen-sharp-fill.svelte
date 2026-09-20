<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9-vwpbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9-vwpbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-japanese-yen-sharp-fill" {...props}></Icon>
