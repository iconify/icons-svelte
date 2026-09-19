<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrc0clbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="nrc0clbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-fill-on-rectangle-angled-fill" {...props}></Icon>
