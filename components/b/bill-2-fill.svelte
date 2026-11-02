<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da1z3qbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da1z3qbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bill-2-fill" {...props}></Icon>
