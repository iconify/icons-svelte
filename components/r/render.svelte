<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aem-iacxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aem-iacxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:render" {...props}></Icon>
