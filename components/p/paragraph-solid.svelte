<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncmu2q-rn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ncmu2q-rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:paragraph-solid" {...props}></Icon>
